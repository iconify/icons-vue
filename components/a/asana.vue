<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if5b9ygfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":251,"height":232};
const content = `<path class="if5b9ygfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:asana" /></template>
