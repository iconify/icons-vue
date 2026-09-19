<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-lju_hdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":417,"height":512};
const content = `<path class="a-lju_hdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:clips" /></template>
