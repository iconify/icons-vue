<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec1pe8byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec1pe8byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-u-circle-solid" /></template>
