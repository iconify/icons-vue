<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq6kcibbx.css';
import '../../css/n/nw_1midni.css';
import '../../css/g/gtxro9plz.css';
import '../../css/t/t228px9jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fq6kcibbx"/><path class="nw_1midni"/><path class="gtxro9plz"/><path class="t228px9jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:information-circle-outline" /></template>
