<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhxnwmbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxnwmbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:amusement-park-castle-bold" /></template>
