<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/d/djif1ebuq.css';
import '../../css/y/y42dvwjda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="djif1ebuq"/><path class="y42dvwjda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:circle-double-up" /></template>
