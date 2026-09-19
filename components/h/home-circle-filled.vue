<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxy0ol00o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxy0ol00o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-circle-filled" /></template>
