<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx92hybfl.css';
import '../../css/d/dmm45_lcf.css';
import '../../css/l/lb7h8tbjg.css';
import '../../css/s/s2e5-v7hd.css';
import '../../css/e/exp3adbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wx92hybfl"/><path class="dmm45_lcf"/><path class="lb7h8tbjg"/><path class="s2e5-v7hd"/><path class="exp3adbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ghidra" /></template>
