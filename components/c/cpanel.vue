<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brmk2qfek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":407.66,"height":240};
const content = `<path class="brmk2qfek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cpanel" /></template>
