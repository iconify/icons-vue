<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uynwg_bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uynwg_bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dice-4" /></template>
