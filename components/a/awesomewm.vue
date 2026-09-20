<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw_7s7aau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw_7s7aau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:awesomewm" /></template>
