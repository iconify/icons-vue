<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc0wjpb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc0wjpb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-2" /></template>
