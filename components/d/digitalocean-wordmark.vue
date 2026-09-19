<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al88j65bh.css';
import '../../css/j/jd1srsr7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="al88j65bh"/><path class="jd1srsr7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:digitalocean-wordmark" /></template>
