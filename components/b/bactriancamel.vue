<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvo1o4byr.css';
import '../../css/q/qzwrsetpw.css';
import '../../css/z/z8xma-crw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nvo1o4byr"/><path class="qzwrsetpw"/><path class="z8xma-crw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bactriancamel" /></template>
