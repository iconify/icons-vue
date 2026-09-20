<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e41sh2w3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":394};
const content = `<path class="e41sh2w3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:blitz" /></template>
