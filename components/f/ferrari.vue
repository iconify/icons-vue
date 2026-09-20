<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q31r1jbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q31r1jbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ferrari" /></template>
