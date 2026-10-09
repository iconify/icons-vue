<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh-egpbpk.css';
import '../../css/p/pzb63_vzh.css';
import '../../css/n/n4ap65bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sh-egpbpk"/><path class="pzb63_vzh"/><path class="n4ap65bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desk-lamp-20" /></template>
