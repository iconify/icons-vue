<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/oy6nqv02f.css';
import '../../css/v/vbgub7z9d.css';
import '../../css/n/nol19vq4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oy6nqv02f"/><path class="vbgub7z9d"/><circle class="nol19vq4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:image-sparkles" /></template>
