<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj3b-5bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-1};
const content = `<path class="aj3b-5bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:glue-f" /></template>
