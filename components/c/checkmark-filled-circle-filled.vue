<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/h/hf6a9qbgm.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGwT4KJeMj"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="hf6a9qbgm"/></mask></defs><circle mask="url(#SVGwT4KJeMj)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:checkmark-filled-circle-filled" /></template>
