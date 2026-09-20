<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omitv2byq.css';
import '../../css/s/s6gb733yj.css';
import '../../css/g/g1kqfibni.css';
import '../../css/x/xy5e245oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omitv2byq"/><path class="s6gb733yj"/><path class="g1kqfibni"/><path class="xy5e245oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freecad" /></template>
