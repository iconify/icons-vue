<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc-34jbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc-34jbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:battery-full-fill" /></template>
