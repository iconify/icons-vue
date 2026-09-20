<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppq-09n2f.css';
import '../../css/l/l72h1vbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ppq-09n2f"/><path clip-rule="evenodd" class="l72h1vbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:doc-solid" /></template>
