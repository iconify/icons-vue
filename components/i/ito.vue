<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljgn8wb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljgn8wb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:ito" /></template>
