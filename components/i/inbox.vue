<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdzaxn_oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdzaxn_oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:inbox" /></template>
