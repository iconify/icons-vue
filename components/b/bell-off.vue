<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzchqyb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzchqyb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bell-off" /></template>
