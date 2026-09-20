<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui9se-bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui9se-bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:bullet-list" /></template>
