<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mneset-vt.css';
import '../../css/i/iha57zbze.css';
import '../../css/x/xrneb2bxe.css';
import '../../css/j/j2xr3seuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mneset-vt"/><path class="iha57zbze"/><path class="xrneb2bxe"/><path class="j2xr3seuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-bus-20" /></template>
