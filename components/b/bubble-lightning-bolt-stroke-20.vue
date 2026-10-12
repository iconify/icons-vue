<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-7j0sgsx.css';
import '../../css/b/bmmy7ztjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a-7j0sgsx"/><path class="bmmy7ztjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-lightning-bolt-stroke-20" /></template>
