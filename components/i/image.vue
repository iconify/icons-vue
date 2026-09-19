<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9cmwo62a.css';
import '../../css/s/si1_fnblv.css';
import '../../css/h/hxfqr2z6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v9cmwo62a"/><path class="si1_fnblv"/><path class="hxfqr2z6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:image" /></template>
