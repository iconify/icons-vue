<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kkkulc1_f.css';
import '../../css/o/opmwddc4w.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGmLoa2ckR"><g class="ft5dv1b6b"><path class="kkkulc1_f"/><path class="opmwddc4w"/></g></mask></defs><path mask="url(#SVGmLoa2ckR)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bag-alt-duotone-line" /></template>
