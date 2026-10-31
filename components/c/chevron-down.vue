<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvnrk-_wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvnrk-_wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:chevron-down" /></template>
