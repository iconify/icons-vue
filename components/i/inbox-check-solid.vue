<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk6ynbs5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk6ynbs5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:inbox-check-solid" /></template>
