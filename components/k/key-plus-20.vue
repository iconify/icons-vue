<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu-d0ccoo.css';
import '../../css/v/vlpd_6j7q.css';
import '../../css/l/lpcghzexh.css';
import '../../css/q/qy_x_gaft.css';
import '../../css/e/evng24apc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zu-d0ccoo"/><path class="vlpd_6j7q"/><path class="lpcghzexh"/><path class="qy_x_gaft"/><path class="evng24apc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-plus-20" /></template>
