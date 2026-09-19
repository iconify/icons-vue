<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7kg3hbvs.css';
import '../../css/i/irdc55aqf.css';
import '../../css/d/di4jzbbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7kg3hbvs"/><path class="irdc55aqf"/><path class="di4jzbbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:construct-outline" /></template>
