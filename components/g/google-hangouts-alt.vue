<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw4_fx-en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw4_fx-en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:google-hangouts-alt" /></template>
