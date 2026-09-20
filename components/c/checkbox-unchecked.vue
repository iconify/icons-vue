<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x04hbkbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="x04hbkbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:checkbox-unchecked" /></template>
