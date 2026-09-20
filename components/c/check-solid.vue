<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrf102bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrf102bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:check-solid" /></template>
