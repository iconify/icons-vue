<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtz-pszql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtz-pszql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-c-octagon-solid" /></template>
