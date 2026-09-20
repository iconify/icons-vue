<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyf75iblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyf75iblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ghost3-filled" /></template>
