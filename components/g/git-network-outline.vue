<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9gmjl-2d.css';
import '../../css/f/fwg5bsbqs.css';
import '../../css/y/y-m3momgu.css';
import '../../css/d/dc1j7wpdw.css';
import '../../css/x/x-czm5bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="g9gmjl-2d"/><circle class="fwg5bsbqs"/><path class="y-m3momgu"/><circle class="dc1j7wpdw"/><path class="x-czm5bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:git-network-outline" /></template>
