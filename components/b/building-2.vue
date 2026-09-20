<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-92gbb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-92gbb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:building-2" /></template>
