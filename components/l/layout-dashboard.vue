<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfbi1bblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfbi1bblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layout-dashboard" /></template>
