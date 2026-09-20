<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoi0s-bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoi0s-bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cypherock" /></template>
