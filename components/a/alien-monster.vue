<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaf7zzb_b.css';
import '../../css/h/hzhb0bcwn.css';
import '../../css/a/aymm9687y.css';
import '../../css/r/rbrc508ky.css';
import '../../css/l/ldneyybya.css';
import '../../css/p/p7u7k5zhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uaf7zzb_b"/><g class="hzhb0bcwn"><path class="aymm9687y"/><path class="rbrc508ky"/><path class="ldneyybya"/><path class="p7u7k5zhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:alien-monster" /></template>
