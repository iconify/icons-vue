<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpe4kgbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zpe4kgbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:logtalk" /></template>
