<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ors3-zf-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ors3-zf-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-up-solid" /></template>
