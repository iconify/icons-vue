<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywu4_4b-u.css';
import '../../css/m/me6xtzbri.css';
import '../../css/z/z3fiy1goj.css';
import '../../css/x/x_umbtwhv.css';
import '../../css/i/ijtms13ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywu4_4b-u"/><path class="me6xtzbri"/><path class="z3fiy1goj"/><path class="x_umbtwhv"/><path class="ijtms13ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:chipmunk" /></template>
