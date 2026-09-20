<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruva7n5ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruva7n5ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-j" /></template>
