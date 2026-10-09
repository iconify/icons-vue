<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1uuebynj.css';
import '../../css/s/se19vpb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z1uuebynj"/><path class="se19vpb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-left-up-48-bold" /></template>
