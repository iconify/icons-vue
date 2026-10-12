<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s_y61bbrf.css';
import '../../css/y/y7rf6wbpp.css';
import '../../css/x/x7-tn3b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s_y61bbrf"/><path class="y7rf6wbpp"/><path class="x7-tn3b9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-code-duotone" /></template>
