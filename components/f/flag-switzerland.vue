<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1t_bgblg.css';
import '../../css/l/ljyjriblh.css';
import '../../css/q/qaf2rb42e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="i1t_bgblg"/><path class="ljyjriblh"/><path class="qaf2rb42e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-switzerland" /></template>
