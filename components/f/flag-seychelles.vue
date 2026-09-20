<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/codjm1acu.css';
import '../../css/h/hggd_7bql.css';
import '../../css/l/lg21m7bsa.css';
import '../../css/f/fs9_qlblc.css';
import '../../css/v/vw_n91w7z.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="codjm1acu"/><path class="hggd_7bql"/><path class="lg21m7bsa"/><path class="fs9_qlblc"/><path class="vw_n91w7z"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-seychelles" /></template>
