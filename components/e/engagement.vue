<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrdhj80fb.css';
import '../../css/p/pob-y2b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrdhj80fb"/><path class="pob-y2b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:engagement" /></template>
