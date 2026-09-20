<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he_rybccd.css';
import '../../css/r/rvl2dhb2g.css';
import '../../css/c/co_1e37mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="he_rybccd"/><path clip-rule="evenodd" class="rvl2dhb2g"/><path class="co_1e37mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:botanix" /></template>
