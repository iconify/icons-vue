<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enuv3ub3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enuv3ub3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hourglass2-filled" /></template>
