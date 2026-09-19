<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea_x7bcxj.css';
import '../../css/i/ii1apz97u.css';
import '../../css/t/t4y5bybeg.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 ea_x7bcxj"/><path class="clr-i-solid clr-i-solid-path-2 ii1apz97u"/><path class="clr-i-solid clr-i-solid-path-3 t4y5bybeg"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:caravan-solid" /></template>
