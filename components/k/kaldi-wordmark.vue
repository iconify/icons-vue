<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjrh6jb6e.css';
import '../../css/q/qpqtl2biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jjrh6jb6e"/><path class="qpqtl2biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kaldi-wordmark" /></template>
