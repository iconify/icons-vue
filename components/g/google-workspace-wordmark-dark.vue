<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whco19wwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":130};
const content = `<path class="whco19wwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-workspace-wordmark-dark" /></template>
