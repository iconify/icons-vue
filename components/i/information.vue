<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzy55k3-q.css';
import '../../css/g/gtbk85xxx.css';
import '../../css/c/cfprd2egi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzy55k3-q"/><path class="gtbk85xxx"/><path class="cfprd2egi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:information" /></template>
