<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtyn5_b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtyn5_b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-outline" /></template>
