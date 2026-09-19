<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu6xx9mid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="wu6xx9mid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:comment" /></template>
