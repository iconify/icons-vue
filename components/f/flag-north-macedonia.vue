<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8cxt48ie.css';
import '../../css/z/z51mj2nbz.css';
import '../../css/z/z6g585zyw.css';
import '../../css/d/dbkz5gqwv.css';
import '../../css/v/vw_tqwb3j.css';
import '../../css/r/rfn52jbce.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><path class="z51mj2nbz"/><path class="z6g585zyw"/><path class="dbkz5gqwv"/><path class="vw_tqwb3j"/><circle class="rfn52jbce"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-north-macedonia" /></template>
