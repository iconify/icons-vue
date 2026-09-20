<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyc-o5rhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyc-o5rhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:a-arrow-down-solid" /></template>
