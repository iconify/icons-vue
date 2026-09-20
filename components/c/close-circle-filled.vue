<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma-rekbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma-rekbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:close-circle-filled" /></template>
