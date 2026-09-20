<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm53gq1ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm53gq1ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hot" /></template>
