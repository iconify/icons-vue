<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh71cgazm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh71cgazm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-right-bold-box-outline" /></template>
