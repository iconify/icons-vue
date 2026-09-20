<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tj6ubqbhj.css';
import '../../css/n/nfu1r0bhd.css';
import '../../css/c/czeiw6b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="tj6ubqbhj"/><rect class="nfu1r0bhd"/><path class="czeiw6b4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:align-end-horizontal" /></template>
