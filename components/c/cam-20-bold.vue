<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7hh0ng0w.css';
import '../../css/c/cdujlmbca.css';
import '../../css/t/tpz02j0hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7hh0ng0w"/><path class="cdujlmbca"/><path class="tpz02j0hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cam-20-bold" /></template>
