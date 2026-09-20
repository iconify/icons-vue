<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2gooybms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2gooybms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:adonisjs" /></template>
