<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eivil5x4j.css';
import '../../css/a/acg_ub67k.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGMdgKseHX"><g class="ft5dv1b6b"><path class="eivil5x4j"/><path class="acg_ub67k"/></g></mask></defs><path mask="url(#SVGMdgKseHX)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folders-line-duotone-line" /></template>
