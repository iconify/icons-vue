<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/lf83cxb8z.css';
import '../../css/o/orlfnvmgi.css';
import '../../css/r/ri7ymhbfz.css';
import '../../css/a/as81pf7bf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJu9P0c0o"><g class="v3_i3wktz"><path class="lf83cxb8z"/><path class="orlfnvmgi"/><path class="ri7ymhbfz"/><path class="as81pf7bf"/></g></mask></defs><path mask="url(#SVGJu9P0c0o)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hourglass-full" /></template>
