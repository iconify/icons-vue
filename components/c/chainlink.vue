<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agfs7ab5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agfs7ab5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:chainlink" /></template>
