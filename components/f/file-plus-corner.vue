<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-5p06bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-5p06bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-plus-corner" /></template>
