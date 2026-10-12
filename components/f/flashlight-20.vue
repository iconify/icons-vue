<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeonhzbov.css';
import '../../css/u/utwwk0b7p.css';
import '../../css/w/wwuvbm56v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zeonhzbov"/><path class="utwwk0b7p"/><path class="wwuvbm56v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flashlight-20" /></template>
