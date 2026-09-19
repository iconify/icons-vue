<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct3bt8zjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct3bt8zjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-key-filled" /></template>
