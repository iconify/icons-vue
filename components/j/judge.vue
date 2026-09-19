<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zc1vi2b-v.css';
import '../../css/b/bi7l6m0-g.css';
import '../../css/y/ydvxzi99r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zc1vi2b-v"/><path class="bi7l6m0-g"/><path class="ydvxzi99r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:judge" /></template>
