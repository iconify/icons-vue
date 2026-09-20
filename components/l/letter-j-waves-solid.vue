<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okody53ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okody53ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-j-waves-solid" /></template>
