<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz5tnpmhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz5tnpmhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-down-left-solid" /></template>
