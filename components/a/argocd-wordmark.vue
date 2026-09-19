<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh3igdb-g.css';
import '../../css/x/xtkb3wptd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lh3igdb-g"/><path class="xtkb3wptd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:argocd-wordmark" /></template>
