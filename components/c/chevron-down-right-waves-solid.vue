<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1ax39u0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ax39u0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-right-waves-solid" /></template>
