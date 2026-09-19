<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifivasbnp.css';
import '../../css/p/ptb97odfw.css';
import '../../css/d/dmmpmib0w.css';
import '../../css/y/yr6a_mbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ifivasbnp"/><path class="ptb97odfw"/><path class="dmmpmib0w"/><path class="yr6a_mbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackpennant" /></template>
