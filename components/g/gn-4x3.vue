<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/c/c1yjnaccy.css';
import '../../css/f/f1--t6a0g.css';
import '../../css/e/eyrc--b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="c1yjnaccy"/><path class="f1--t6a0g"/><path class="eyrc--b5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:gn-4x3" /></template>
