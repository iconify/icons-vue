<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iic6q4bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iic6q4bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:battery-empty" /></template>
