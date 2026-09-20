<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz3rf8b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz3rf8b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-clear" /></template>
