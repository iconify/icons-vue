<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2we-hbpo.css';
import '../../css/b/bd2w689nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z2we-hbpo"/><path class="bd2w689nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bell-strike-fill-20" /></template>
