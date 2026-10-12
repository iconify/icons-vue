<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j4r65kbin.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/h/hftn89tbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j4r65kbin"/><path class="s1a2eew1e"/><path clip-rule="evenodd" class="hftn89tbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:contact-duotone" /></template>
