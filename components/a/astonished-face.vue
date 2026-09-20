<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7hstbmu.css';
import '../../css/v/vo7mfybzy.css';
import '../../css/c/ca1jkw6hv.css';
import '../../css/k/k4z7zsbhp.css';
import '../../css/u/u_6rennll.css';
import '../../css/c/c9mfofy0x.css';
import '../../css/b/bj3257nlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><path class="vo7mfybzy"/><path class="ca1jkw6hv"/><circle class="k4z7zsbhp"/><path class="u_6rennll"/><path class="c9mfofy0x"/><circle class="bj3257nlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:astonished-face" /></template>
