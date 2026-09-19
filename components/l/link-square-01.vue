<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw0eq05ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw0eq05ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:link-square-01" /></template>
