<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muhulxb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muhulxb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-9-solid" /></template>
