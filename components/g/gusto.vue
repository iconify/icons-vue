<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt9ac1boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt9ac1boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gusto" /></template>
