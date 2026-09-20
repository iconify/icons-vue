<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rytk8ivix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rytk8ivix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-24" /></template>
