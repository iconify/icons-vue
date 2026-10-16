<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdltw8kvl.css';
import '../../css/x/x-t9vyu4u.css';
import '../../css/m/mdhfcqbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rdltw8kvl"/><path class="x-t9vyu4u"/><path class="mdhfcqbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-pitch-48-bold" /></template>
