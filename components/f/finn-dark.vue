<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_tvfq6mb.css';
import '../../css/t/tfa5mdbsb.css';
import '../../css/i/iufs412sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_tvfq6mb"/><path class="tfa5mdbsb"/><path class="iufs412sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:finn-dark" /></template>
