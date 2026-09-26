<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng4igtd1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ng4igtd1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-outline" /></template>
