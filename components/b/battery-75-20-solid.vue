<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myplm-wqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="myplm-wqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-75-20-solid" /></template>
