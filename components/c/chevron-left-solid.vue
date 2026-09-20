<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzk-88c7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzk-88c7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-left-solid" /></template>
