<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl3mqwbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl3mqwbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:informatica" /></template>
