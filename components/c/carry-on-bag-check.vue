<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf4gv2feu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf4gv2feu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:carry-on-bag-check" /></template>
