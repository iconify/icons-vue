<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k_we9dbkd.css';
import '../../css/q/qvv9bdbon.css';
import '../../css/n/n7lafqbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k_we9dbkd"/><path class="qvv9bdbon"/><path class="n7lafqbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:danger" /></template>
