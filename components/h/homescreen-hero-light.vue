<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imvewngax.css';
import '../../css/h/hexr8-bsz.css';
import '../../css/n/nadauofsf.css';
import '../../css/y/y--w-mb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imvewngax"/><path class="hexr8-bsz"/><path class="nadauofsf"/><path class="y--w-mb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homescreen-hero-light" /></template>
