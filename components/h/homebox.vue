<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmqbshfgv.css';
import '../../css/f/fkwnb7hig.css';
import '../../css/f/f-cbqwb3y.css';
import '../../css/v/vo2_w5r4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmqbshfgv"/><path class="fkwnb7hig"/><path class="f-cbqwb3y"/><path class="vo2_w5r4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homebox" /></template>
