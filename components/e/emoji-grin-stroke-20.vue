<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo825-vwk.css';
import '../../css/z/zcqk8ssib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eo825-vwk"/><path class="zcqk8ssib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-grin-stroke-20" /></template>
