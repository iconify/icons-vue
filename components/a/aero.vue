<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hefuzsyto.css';
import '../../css/h/hy2durjjx.css';
import '../../css/y/y3v2sl6-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":51.74,"height":70};
const content = `<path class="hefuzsyto"/><path class="hy2durjjx"/><path class="y3v2sl6-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:aero" /></template>
