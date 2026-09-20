<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/f/f9uqp6_rc.css';
import '../../css/k/kfawhz9uz.css';
import '../../css/t/t-dq_9l_t.css';
import '../../css/b/bal1zy7-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="f9uqp6_rc"/><path class="kfawhz9uz"/><path class="t-dq_9l_t"/><path class="bal1zy7-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:coins" /></template>
