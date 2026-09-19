<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c13bt8b3z.css';
import '../../css/l/lgvvujlva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c13bt8b3z"/><path class="lgvvujlva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hand-left-outline" /></template>
