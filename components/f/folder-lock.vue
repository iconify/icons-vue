<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1iw_e_7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1iw_e_7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-lock" /></template>
