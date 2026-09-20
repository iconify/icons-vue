<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kz9epiigo.css';
import '../../css/m/mswo_dbyo.css';
import '../../css/b/b1_g2rb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<g class="cuyn6tgcc"><circle class="kz9epiigo"/><circle class="mswo_dbyo"/><path class="b1_g2rb3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:flickr-circle" /></template>
