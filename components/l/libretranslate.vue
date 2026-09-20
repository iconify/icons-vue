<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3s_f7bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3s_f7bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:libretranslate" /></template>
