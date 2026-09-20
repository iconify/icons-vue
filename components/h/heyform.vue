<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj-lznb8w.css';
import '../../css/h/hq5gb_4kr.css';
import '../../css/i/iv7xugjxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oj-lznb8w"/><path class="hq5gb_4kr"/><path class="iv7xugjxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heyform" /></template>
