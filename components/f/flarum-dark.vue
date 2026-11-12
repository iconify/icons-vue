<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cutyt3biv.css';
import '../../css/x/xvo7kubqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cutyt3biv"/><path class="xvo7kubqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flarum-dark" /></template>
