<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfsug6rjk.css';
import '../../css/j/jej7e325s.css';
import '../../css/f/fpvpjcd5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qfsug6rjk"/><path class="jej7e325s"/><path class="fpvpjcd5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:bell" /></template>
