<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1mjunbsu.css';
import '../../css/c/ce9wo0wqz.css';
import '../../css/s/s_xed7b6t.css';
import '../../css/i/ie__sd2_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="n1mjunbsu"><circle class="ce9wo0wqz"/><path class="s_xed7b6t"/><path class="ie__sd2_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clerk-dark" /></template>
