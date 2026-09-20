<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f67q75bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f67q75bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jetblue" /></template>
