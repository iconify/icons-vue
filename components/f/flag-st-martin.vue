<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkq7-hbwz.css';
import '../../css/p/pi7jdd7uf.css';
import '../../css/b/bzun-yi8p.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><path class="pi7jdd7uf"/><path class="bzun-yi8p"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-st-martin" /></template>
