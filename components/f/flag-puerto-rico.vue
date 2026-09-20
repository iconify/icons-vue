<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkq7-hbwz.css';
import '../../css/q/qohud7bbt.css';
import '../../css/m/mwl13xblr.css';
import '../../css/c/c111f0qvj.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><path class="qohud7bbt"/><path class="mwl13xblr"/><path class="c111f0qvj"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-puerto-rico" /></template>
