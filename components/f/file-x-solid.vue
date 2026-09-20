<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz9-nx68p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz9-nx68p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:file-x-solid" /></template>
