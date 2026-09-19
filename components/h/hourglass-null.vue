<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/lf83cxb8z.css';
import '../../css/o/orlfnvmgi.css';
import '../../css/r/ri7ymhbfz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJGp6eckF"><g class="v3_i3wktz"><path class="lf83cxb8z"/><path class="orlfnvmgi"/><path class="ri7ymhbfz"/></g></mask></defs><path mask="url(#SVGJGp6eckF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hourglass-null" /></template>
