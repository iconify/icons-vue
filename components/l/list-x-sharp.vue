<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfmbv0bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfmbv0bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-x-sharp" /></template>
