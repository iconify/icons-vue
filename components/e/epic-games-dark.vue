<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj334wbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25.548,"height":29.501,"left":3.227,"top":1.25};
const content = `<path class="oj334wbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:epic-games-dark" /></template>
