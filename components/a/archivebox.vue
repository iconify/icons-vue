<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zidfd5b0r.css';
import '../../css/w/wb4b4ktjg.css';
import '../../css/t/tgdoe1bss.css';
import '../../css/c/cbokru48w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zidfd5b0r"/><path class="wb4b4ktjg"/><path class="tgdoe1bss"/><path class="cbokru48w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:archivebox" /></template>
