<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r86rvjbis.css';
import '../../css/b/b-hc40bpi.css';
import '../../css/z/zlrqd59ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r86rvjbis"/><path class="b-hc40bpi"/><path class="zlrqd59ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:character-decimal" /></template>
