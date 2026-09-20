<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unl4ioy1a.css';
import '../../css/u/u27h525fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unl4ioy1a"/><path class="u27h525fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inkscape" /></template>
