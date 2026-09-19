<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw7wwe3lc.css';
import '../../css/o/ovk3-rb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kw7wwe3lc"/><path class="ovk3-rb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:creative-commons-remix" /></template>
