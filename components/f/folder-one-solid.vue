<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upts52bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upts52bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-one-solid" /></template>
