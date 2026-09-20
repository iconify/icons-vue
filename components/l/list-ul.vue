<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/her-4fbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="her-4fbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:list-ul" /></template>
