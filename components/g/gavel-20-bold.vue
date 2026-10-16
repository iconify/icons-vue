<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1ckqlb3r.css';
import '../../css/l/lhsg4trxw.css';
import '../../css/o/ozsbau3sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y1ckqlb3r"/><path class="lhsg4trxw"/><path class="ozsbau3sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gavel-20-bold" /></template>
