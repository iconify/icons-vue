<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaoxfqbbl.css';
import '../../css/f/fh4kjpb7i.css';
import '../../css/q/q4s8-jw3r.css';
import '../../css/r/rf907sb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uaoxfqbbl"/><path class="fh4kjpb7i"/><path class="q4s8-jw3r"/><path class="rf907sb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackscissors" /></template>
