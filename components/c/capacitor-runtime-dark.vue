<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbhczis_n.css';
import '../../css/g/g6y54xlpm.css';
import '../../css/u/up9gopgdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbhczis_n"/><path class="g6y54xlpm"/><path class="up9gopgdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:capacitor-runtime-dark" /></template>
