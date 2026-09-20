<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smwwurb-l.css';
import '../../css/r/r2bxk5btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="smwwurb-l"/><path class="r2bxk5btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:building-real-eastate-location" /></template>
