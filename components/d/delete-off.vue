<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gucaxcqay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gucaxcqay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:delete-off" /></template>
