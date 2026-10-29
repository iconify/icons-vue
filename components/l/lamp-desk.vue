<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg_chdsru.css';
import '../../css/t/tvvddzg0c.css';
import '../../css/o/ouv_rburk.css';
import '../../css/d/dpxfv0boz.css';
import '../../css/q/q2hww7baa.css';
import '../../css/r/ruuuk979k.css';
import '../../css/t/tmf1gsurg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg_chdsru wm-shadow"/><path class="tvvddzg0c wm-k"/><path class="ouv_rburk wm-k"/><path class="dpxfv0boz wm-k"/><path class="q2hww7baa wm-k"/><path class="ruuuk979k wm-k"/><path class="tmf1gsurg wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:lamp-desk" /></template>
