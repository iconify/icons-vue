<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5iso1b0c.css';
import '../../css/u/ul7vggbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f5iso1b0c"/><path class="ul7vggbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:container-image" /></template>
