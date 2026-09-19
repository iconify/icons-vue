<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odd7xt2tc.css';
import '../../css/j/jt3_i6qzm.css';
import '../../css/l/l_3itzz6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odd7xt2tc"/><circle class="jt3_i6qzm"/><path class="l_3itzz6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-rocket" /></template>
