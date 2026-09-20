<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7loe433b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7loe433b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bluetooth-filled" /></template>
