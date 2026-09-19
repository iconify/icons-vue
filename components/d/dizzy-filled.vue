<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfc90oerk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfc90oerk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dizzy-filled" /></template>
