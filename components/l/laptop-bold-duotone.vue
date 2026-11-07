<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8d4-cc9w.css';
import '../../css/p/p8mr26bfo.css';
import '../../css/g/g4j5pwbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8d4-cc9w"/><path clip-rule="evenodd" class="p8mr26bfo"/><path class="g4j5pwbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-bold-duotone" /></template>
