<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag5m9z64z.css';
import '../../css/z/z5kljvobp.css';
import '../../css/i/iv0739boz.css';
import '../../css/y/ynuwzd5vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ag5m9z64z"/><path class="z5kljvobp"/><path class="iv0739boz"/><path class="ynuwzd5vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:filing-cabinet" /></template>
