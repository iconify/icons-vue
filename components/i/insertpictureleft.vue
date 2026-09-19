<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kolw2mbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="kolw2mbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:insertpictureleft" /></template>
