<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2x65obhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2x65obhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fontforge" /></template>
