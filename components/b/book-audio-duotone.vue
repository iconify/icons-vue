<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ora8653hh.css';
import '../../css/s/ssh18kvpm.css';
import '../../css/c/ce2pf8b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ora8653hh"/><path class="ssh18kvpm"/><path class="ce2pf8b6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-audio-duotone" /></template>
