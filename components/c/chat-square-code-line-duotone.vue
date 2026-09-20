<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b0dyb4b4v.css';
import '../../css/s/sej9af0wr.css';
import '../../css/g/gwjck2cdm.css';
import '../../css/e/eq3frqb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b0dyb4b4v"/><path class="sej9af0wr"/><path class="gwjck2cdm"/><path class="eq3frqb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-code-line-duotone" /></template>
