<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv2x-ef6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv2x-ef6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:eye-slash-solid" /></template>
