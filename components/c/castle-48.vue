<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwrb__blp.css';
import '../../css/h/hzh_8obcm.css';
import '../../css/w/w77hsxbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwrb__blp"/><path class="hzh_8obcm"/><path class="w77hsxbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:castle-48" /></template>
