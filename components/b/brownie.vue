<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2sb_fb7f.css';
import '../../css/c/c__4199fc.css';
import '../../css/f/fjbbd-pcw.css';
import '../../css/r/rp4fbybhh.css';
import '../../css/g/g2n2btbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i2sb_fb7f"/><path class="c__4199fc"/><path class="fjbbd-pcw"/><path class="rp4fbybhh"/><path class="g2n2btbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:brownie" /></template>
