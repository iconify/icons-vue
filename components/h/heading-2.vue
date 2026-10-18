<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktnrw8xcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktnrw8xcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-2" /></template>
