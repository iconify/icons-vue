<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttw1ccb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttw1ccb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barbell-line" /></template>
