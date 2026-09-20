<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs4pb60ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs4pb60ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box-3-filled" /></template>
