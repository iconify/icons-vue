<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8cxt48ie.css';
import '../../css/l/lx7mkia0m.css';
import '../../css/t/tsvbfvbzz.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><path class="lx7mkia0m"/><path class="tsvbfvbzz"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-madagascar" /></template>
