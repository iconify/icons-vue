<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftrudtbys.css';
import '../../css/g/gnd-n5ber.css';
import '../../css/z/zawixke2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ftrudtbys"/><path class="gnd-n5ber"/><path class="zawixke2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-melt-20-bold" /></template>
