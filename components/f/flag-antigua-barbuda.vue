<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkq7-hbwz.css';
import '../../css/u/u9hq09b6k.css';
import '../../css/u/ukqcribus.css';
import '../../css/o/otq39xo5k.css';
import '../../css/q/qgfsrx38k.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><path class="u9hq09b6k"/><path class="ukqcribus"/><path class="otq39xo5k"/><path class="qgfsrx38k"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-antigua-barbuda" /></template>
