<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prj2dacnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prj2dacnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-full" /></template>
