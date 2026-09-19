<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlwwq9bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mlwwq9bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:file-archive" /></template>
