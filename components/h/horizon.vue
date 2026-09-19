<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alwq3rdnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="alwq3rdnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:horizon" /></template>
