<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxmby0bbg.css';
import '../../css/b/bxhkq1b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lxmby0bbg"/><path class="bxhkq1b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:brightness" /></template>
