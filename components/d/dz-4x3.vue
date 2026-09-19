<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6jbekf4h.css';
import '../../css/x/xbzc92bph.css';
import '../../css/h/htn4j8b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="y6jbekf4h"/><path class="xbzc92bph"/><path class="htn4j8b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:dz-4x3" /></template>
