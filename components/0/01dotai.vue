<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s04m4zjux.css';
import '../../css/j/jlzxp4qwe.css';
import '../../css/q/qtt4sxbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s04m4zjux"><path class="jlzxp4qwe"/><ellipse class="qtt4sxbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:01dotai" /></template>
