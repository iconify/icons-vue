<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh2ph_5cm.css';
import '../../css/b/brj919_4l.css';
import '../../css/i/itoigib-k.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/d/dm8dtzb9t.css';
import '../../css/p/p6-p-0qyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uh2ph_5cm"/><path class="brj919_4l"/><path class="itoigib-k"/><g class="brzn_0bpr"><path class="dm8dtzb9t"/><path class="p6-p-0qyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:circle-with-right-half-black" /></template>
