<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/sd5pw-b8u.css';
import '../../css/m/mitl-8btu.css';
import '../../css/p/pod1yswni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sd5pw-b8u"/><path class="mitl-8btu"/><path class="pod1yswni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:learning" /></template>
