<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h2xz0_bat.css';
import '../../css/w/wbfa45b6c.css';
import '../../css/j/j-46o3b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h2xz0_bat"/><path class="wbfa45b6c"/><path class="j-46o3b4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folders-duotone" /></template>
