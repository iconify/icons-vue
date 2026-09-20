<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rycq64tst.css';
import '../../css/c/c18ewnbwj.css';
import '../../css/y/yl94r0wtm.css';
import '../../css/p/priknnbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rycq64tst"/><path class="c18ewnbwj"/><path class="yl94r0wtm"/><path class="priknnbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logwell" /></template>
