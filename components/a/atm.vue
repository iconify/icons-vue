<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7pevvpvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7pevvpvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:atm" /></template>
