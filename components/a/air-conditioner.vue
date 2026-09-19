<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkgxzpbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkgxzpbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:air-conditioner" /></template>
