<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmzra2-rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmzra2-rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-2-solid" /></template>
