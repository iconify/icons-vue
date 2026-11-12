<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igt5iubxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="igt5iubxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elysian-dark" /></template>
