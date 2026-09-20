<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dluanabqy.css';
import '../../css/n/naeprdbjc.css';
import '../../css/a/abc-_riwo.css';
import '../../css/x/xrvzlggpv.css';
import '../../css/g/gxucjjbuw.css';
import '../../css/c/cfrb6cbcz.css';
import '../../css/e/e4zfowz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="dluanabqy"/><path class="naeprdbjc"/><path class="abc-_riwo"/><path class="xrvzlggpv"/><path class="gxucjjbuw"/><path class="cfrb6cbcz"/><path class="e4zfowz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:input-numbers" /></template>
