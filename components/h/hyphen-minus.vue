<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg9vbp76i.css';
import '../../css/i/ilkd3ex7e.css';
import '../../css/w/wo110wbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zg9vbp76i"/><path class="ilkd3ex7e"/><path class="wo110wbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hyphen-minus" /></template>
