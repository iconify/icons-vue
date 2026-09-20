<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgeel1b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgeel1b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:file-plus-line" /></template>
