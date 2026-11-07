<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g7e2eab1a.css';
import '../../css/u/u-2m9hbse.css';
import '../../css/v/vmccjbb6s.css';
import '../../css/a/a3scpvo1f.css';
import '../../css/e/eck4ylbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="g7e2eab1a"/><path class="u-2m9hbse"/><path class="vmccjbb6s"/><path class="a3scpvo1f"/><path class="eck4ylbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-stars-linear" /></template>
