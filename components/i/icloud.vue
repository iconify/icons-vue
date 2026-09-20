<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzlascb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzlascb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:icloud" /></template>
