<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxeuqzmsn.css';
import '../../css/z/z1--w73xm.css';
import '../../css/q/q3c4j-bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxeuqzmsn"/><path class="z1--w73xm"/><path class="q3c4j-bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-clipboard" /></template>
