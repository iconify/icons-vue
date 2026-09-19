<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh377bbur.css';
import '../../css/m/mrupvohhm.css';
import '../../css/r/rppc_db6b.css';
import '../../css/m/mm6yhpb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sh377bbur"/><path class="mrupvohhm"/><path class="rppc_db6b"/><path class="mm6yhpb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lowerleftpen" /></template>
