<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/had4r1bdj.css';
import '../../css/w/wjz6iob6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="had4r1bdj"/><path class="wjz6iob6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:inbox-stack-16-solid" /></template>
