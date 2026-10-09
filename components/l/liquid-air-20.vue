<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt2mfkbnd.css';
import '../../css/d/d_ox8aczn.css';
import '../../css/k/k7qteslrh.css';
import '../../css/r/r3am92kyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kt2mfkbnd"/><path class="d_ox8aczn"/><path class="k7qteslrh"/><path class="r3am92kyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:liquid-air-20" /></template>
