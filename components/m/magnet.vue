<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4bw4gbbn.css';
import '../../css/c/czndeu-mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4bw4gbbn"/><path class="czndeu-mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:magnet" /></template>
