<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-z4ovd-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-z4ovd-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:file-warning" /></template>
