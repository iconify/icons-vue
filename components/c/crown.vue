<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceu87zb9i.css';
import '../../css/u/uwvn7obqq.css';
import '../../css/b/buhkhbh6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ceu87zb9i"/><path class="uwvn7obqq"/><path class="buhkhbh6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:crown" /></template>
