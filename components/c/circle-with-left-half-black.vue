<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebpu-5arf.css';
import '../../css/n/n9gulmzpi.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/d/dm8dtzb9t.css';
import '../../css/p/p6-p-0qyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ebpu-5arf"/><path class="n9gulmzpi"/><g class="brzn_0bpr"><path class="dm8dtzb9t"/><path class="p6-p-0qyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:circle-with-left-half-black" /></template>
