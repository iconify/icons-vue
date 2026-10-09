<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtbad_v3a.css';
import '../../css/z/zlmlrhbpp.css';
import '../../css/w/w_ns1hbzc.css';
import '../../css/n/nhv_i6bfk.css';
import '../../css/v/vra7nyw8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtbad_v3a"/><path class="zlmlrhbpp"/><path class="w_ns1hbzc"/><path class="nhv_i6bfk"/><path class="vra7nyw8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-handover-48-bold" /></template>
