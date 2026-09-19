<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck5l6tb3a.css';
import '../../css/t/tx2p9khav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ck5l6tb3a"/><path class="tx2p9khav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:group" /></template>
