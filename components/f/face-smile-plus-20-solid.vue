<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waqc77b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="waqc77b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-smile-plus-20-solid" /></template>
