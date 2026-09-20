<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm7rx68mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm7rx68mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-right-up-solid" /></template>
