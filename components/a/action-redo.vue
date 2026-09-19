<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkz65tbzv.css';
import '../../css/b/bm74p9apf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkz65tbzv"/><path class="bm74p9apf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:action-redo" /></template>
