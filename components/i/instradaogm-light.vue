<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyezo-ikf.css';
import '../../css/h/hw02_8bnp.css';
import '../../css/d/d978pz0hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vyezo-ikf"/><path class="hw02_8bnp"/><path class="d978pz0hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instradaogm-light" /></template>
