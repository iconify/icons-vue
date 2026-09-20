<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_2kcdb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_2kcdb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bug-report-filled" /></template>
