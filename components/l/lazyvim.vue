<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm4fpf_uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm4fpf_uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lazyvim" /></template>
