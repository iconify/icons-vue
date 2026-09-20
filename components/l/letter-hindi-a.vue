<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ua-8bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ua-8bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:letter-hindi-a" /></template>
