<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zllmftbax.css';
import '../../css/k/kot2fq0bc.css';
import '../../css/a/a4kaplbpc.css';
import '../../css/k/k2rcg5b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zllmftbax"/><path class="kot2fq0bc"/><path class="a4kaplbpc"/><path class="k2rcg5b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:magnet-outline" /></template>
