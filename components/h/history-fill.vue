<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqf70vd_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqf70vd_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-fill" /></template>
