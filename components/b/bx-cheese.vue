<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi9h__ikp.css';
import '../../css/h/hwt2tuv6e.css';
import '../../css/j/j_kppeg2r.css';
import '../../css/t/tfw8j54dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi9h__ikp"/><circle class="hwt2tuv6e"/><circle class="j_kppeg2r"/><circle class="tfw8j54dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cheese" /></template>
