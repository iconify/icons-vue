<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5546eb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5546eb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:arrow-right-long" /></template>
