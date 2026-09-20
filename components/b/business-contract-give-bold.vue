<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oej-_gbmt.css';
import '../../css/e/ezxsfzb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oej-_gbmt"/><path class="ezxsfzb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:business-contract-give-bold" /></template>
