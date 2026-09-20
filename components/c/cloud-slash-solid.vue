<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwxihp0nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwxihp0nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-slash-solid" /></template>
