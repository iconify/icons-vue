<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mutf_sboy.css';
import '../../css/g/gdwd5felf.css';
import '../../css/p/p42fz6t_u.css';
import '../../css/z/zgmcztboz.css';
import '../../css/q/qyy895bgd.css';
import '../../css/s/s9fbtob_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mutf_sboy wm-shadow"/><path class="gdwd5felf wm-k"/><path class="p42fz6t_u wm-k"/><path class="wm-k zgmcztboz"/><path class="qyy895bgd wm-k"/><path class="s9fbtob_a wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:arrow-up-left" /></template>
