<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u98q4jbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="u98q4jbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:innerborders" /></template>
