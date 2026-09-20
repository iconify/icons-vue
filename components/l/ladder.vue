<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qui3_ycrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qui3_ycrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ladder" /></template>
