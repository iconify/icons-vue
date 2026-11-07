<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s9d3aj35l.css';
import '../../css/b/bzgri7b_b.css';
import '../../css/x/xc7mudb6e.css';
import '../../css/j/jgur5aczj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s9d3aj35l"/><path class="bzgri7b_b"/><path class="xc7mudb6e"/><path class="jgur5aczj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-case-open-broken" /></template>
