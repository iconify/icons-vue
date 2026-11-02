<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg3rie7kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg3rie7kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bowl-2-fill" /></template>
