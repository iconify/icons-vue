<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-0lfcb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="q-0lfcb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-both-direction-vertical-1" /></template>
