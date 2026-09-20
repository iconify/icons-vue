<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb5z0sboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb5z0sboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-x-solid" /></template>
