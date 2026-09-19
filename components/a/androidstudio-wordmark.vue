<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1kda8_rz.css';
import '../../css/b/bi8vxwb8z.css';
import '../../css/v/vbaged_wf.css';
import '../../css/l/l1ghlxbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r1kda8_rz"/><path class="bi8vxwb8z"/><path class="vbaged_wf"/><circle class="l1ghlxbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:androidstudio-wordmark" /></template>
