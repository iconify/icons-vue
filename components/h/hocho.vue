<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhl50ubkh.css';
import '../../css/s/s05wzqbji.css';
import '../../css/t/ti-1rqbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhl50ubkh"/><path class="s05wzqbji"/><path class="ti-1rqbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hocho" /></template>
