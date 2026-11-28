<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avtewbcvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avtewbcvp primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-sharp-duotone" /></template>
