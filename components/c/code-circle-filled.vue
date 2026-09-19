<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn56m8vwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn56m8vwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-circle-filled" /></template>
