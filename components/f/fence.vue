<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8mx1cb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8mx1cb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:fence" /></template>
