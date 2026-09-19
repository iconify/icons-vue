<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnxov3bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnxov3bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:instagram" /></template>
