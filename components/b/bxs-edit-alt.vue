<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-cb5xbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-cb5xbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-edit-alt" /></template>
