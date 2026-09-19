<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj5p2mlzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qj5p2mlzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:eagle" /></template>
