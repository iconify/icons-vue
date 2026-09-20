<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4jw8wbpz.css';
import '../../css/b/bnnoq8bqn.css';
import '../../css/e/ejqbi5b-l.css';
import '../../css/i/i3ff7jbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="f4jw8wbpz"/><circle class="bnnoq8bqn"/><path class="ejqbi5b-l"/><path class="i3ff7jbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:biohazard" /></template>
