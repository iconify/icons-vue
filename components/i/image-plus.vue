<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/ajbswkpvd.css';
import '../../css/b/b4fcxnb0b.css';
import '../../css/n/nol19vq4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ajbswkpvd"/><path class="b4fcxnb0b"/><circle class="nol19vq4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:image-plus" /></template>
