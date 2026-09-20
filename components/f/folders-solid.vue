<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-hvtj13o.css';
import '../../css/n/nfzvdkovf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g-hvtj13o"/><path class="nfzvdkovf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folders-solid" /></template>
