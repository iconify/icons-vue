<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyjklpbqy.css';
import '../../css/t/t_y32l19z.css';
import '../../css/t/tb62sjbsx.css';
import '../../css/m/mf4zhw8on.css';
import '../../css/d/dcil5bbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="eyjklpbqy"/><path class="t_y32l19z"/><rect class="tb62sjbsx"/><rect class="mf4zhw8on"/><path class="dcil5bbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:library-outline" /></template>
