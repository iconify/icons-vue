<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xlhb4cbxr.css';
import '../../css/z/zoslq7bwc.css';
import '../../css/f/fd7qipbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xlhb4cbxr"/><path class="zoslq7bwc"/><path class="fd7qipbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:eye" /></template>
