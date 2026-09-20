<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx7-hobba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx7-hobba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-check-solid" /></template>
