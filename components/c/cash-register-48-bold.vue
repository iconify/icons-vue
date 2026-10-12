<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb0rmwb_o.css';
import '../../css/n/n_tg6m2do.css';
import '../../css/f/f_6f76wwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yb0rmwb_o"/><path class="n_tg6m2do"/><path class="f_6f76wwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cash-register-48-bold" /></template>
