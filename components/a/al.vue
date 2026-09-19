<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s4pjuacnm.css';
import '../../css/s/sjr9l67ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s4pjuacnm"/><path class="sjr9l67ze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:al" /></template>
