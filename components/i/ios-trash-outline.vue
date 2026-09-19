<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uockbibpw.css';
import '../../css/l/lpkskg0rz.css';
import '../../css/k/ka-x0cbqx.css';
import '../../css/m/mce-y_bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uockbibpw"/><path class="lpkskg0rz"/><path class="ka-x0cbqx"/><path class="mce-y_bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-trash-outline" /></template>
