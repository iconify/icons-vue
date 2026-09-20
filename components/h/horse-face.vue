<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm63vpn3v.css';
import '../../css/g/g4io50bld.css';
import '../../css/n/n_kgd6bgm.css';
import '../../css/n/nroc7pb1g.css';
import '../../css/q/q9phk0b9d.css';
import '../../css/s/syt_cqbfy.css';
import '../../css/y/yt__tbc8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cm63vpn3v"/><path class="g4io50bld"/><path class="n_kgd6bgm"/><path class="nroc7pb1g"/><path class="q9phk0b9d"/><path class="syt_cqbfy"/><circle class="yt__tbc8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:horse-face" /></template>
