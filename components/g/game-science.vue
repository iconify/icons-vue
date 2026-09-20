<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_081rb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_081rb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:game-science" /></template>
