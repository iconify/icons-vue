<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al7hf0ijn.css';
import '../../css/p/p5oxreb1k.css';
import '../../css/q/qyivhdcvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="al7hf0ijn"/><path class="p5oxreb1k"/><path class="qyivhdcvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:documentation" /></template>
