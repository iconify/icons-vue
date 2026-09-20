<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px824wbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px824wbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-right-waves-solid" /></template>
