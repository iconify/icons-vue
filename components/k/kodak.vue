<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw7l9eb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw7l9eb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kodak" /></template>
