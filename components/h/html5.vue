<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u779_db3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u779_db3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:html5" /></template>
