<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6yn8gb3f.css';
import '../../css/i/ipg66nb4h.css';
import '../../css/s/syqz6bc1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6yn8gb3f"/><path class="ipg66nb4h"/><path class="syqz6bc1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:deciduoustree" /></template>
