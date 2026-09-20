<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw9z6cbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kw9z6cbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:backblaze-dark" /></template>
