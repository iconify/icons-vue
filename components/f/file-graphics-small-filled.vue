<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj_rtjbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zj_rtjbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-graphics-small-filled" /></template>
