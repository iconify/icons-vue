<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtma55bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtma55bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-saving-done-01" /></template>
