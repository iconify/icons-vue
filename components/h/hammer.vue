<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib08t_4oj.css';
import '../../css/e/epf28maej.css';
import '../../css/g/gg9khyk8m.css';
import '../../css/e/emqiupbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ib08t_4oj"/><path class="epf28maej"/><path class="gg9khyk8m"/><path class="emqiupbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hammer" /></template>
