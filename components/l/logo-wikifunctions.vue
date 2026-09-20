<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6v83qbqk.css';
import '../../css/c/c1ks9gyit.css';
import '../../css/a/azcv31byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6v83qbqk"/><path class="c1ks9gyit"/><path class="azcv31byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikifunctions" /></template>
