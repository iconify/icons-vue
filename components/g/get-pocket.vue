<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xym44vlld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xym44vlld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:get-pocket" /></template>
