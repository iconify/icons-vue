<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kqpg5iqap.css';
import '../../css/g/g5oxg6tvq.css';
import '../../css/w/wh274hb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kqpg5iqap"/><path class="g5oxg6tvq"/><path class="wh274hb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-pen-duotone" /></template>
