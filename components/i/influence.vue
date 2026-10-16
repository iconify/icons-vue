<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p56r-9gea.css';
import '../../css/x/xx_qfjbte.css';
import '../../css/y/y08wrnukj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p56r-9gea"/><g transform="matrix(.75 0 0 .75 8 8)"><circle class="xx_qfjbte"/><path class="y08wrnukj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:influence" /></template>
