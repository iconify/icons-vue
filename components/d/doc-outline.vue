<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt-uee45l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qt-uee45l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:doc-outline" /></template>
