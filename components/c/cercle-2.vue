<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfaj228ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfaj228ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-2" /></template>
