<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjqu0sf-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjqu0sf-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-big-down-left-solid" /></template>
