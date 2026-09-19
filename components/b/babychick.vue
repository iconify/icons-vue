<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsoix_jkw.css';
import '../../css/f/f_yv0yb3g.css';
import '../../css/p/pr0kgdb0u.css';
import '../../css/c/cvziz8baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rsoix_jkw"/><path class="f_yv0yb3g"/><path class="pr0kgdb0u"/><path class="cvziz8baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:babychick" /></template>
