<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn7behsca.css';
import '../../css/a/av17rs-8h.css';
import '../../css/u/uvs-qupzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hn7behsca"/><path class="av17rs-8h"/><path class="uvs-qupzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gleam" /></template>
