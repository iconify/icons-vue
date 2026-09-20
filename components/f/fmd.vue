<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeyfkhb4r.css';
import '../../css/t/t7d2d5bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jeyfkhb4r"/><path class="t7d2d5bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fmd" /></template>
