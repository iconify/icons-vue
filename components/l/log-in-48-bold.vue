<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryya2cmsp.css';
import '../../css/m/mqlcs9bpx.css';
import '../../css/f/f_n_iqb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ryya2cmsp"/><path class="mqlcs9bpx"/><path class="f_n_iqb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:log-in-48-bold" /></template>
