<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c7allhbye.css';
import '../../css/l/lxs-gy18y.css';
import '../../css/j/j7r7czb3p.css';
import '../../css/u/uih-rf4pm.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGrb3aaePT"><g class="ft5dv1b6b"><path class="c7allhbye"/><path class="lxs-gy18y"/><circle class="j7r7czb3p"/><path class="uih-rf4pm"/></g></mask></defs><path mask="url(#SVGrb3aaePT)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-search-duotone-light" /></template>
