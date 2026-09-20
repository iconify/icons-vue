<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g61do7b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g61do7b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bug-2-line" /></template>
