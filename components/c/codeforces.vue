<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj5f6ibmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj5f6ibmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codeforces" /></template>
