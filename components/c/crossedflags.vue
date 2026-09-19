<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/astguezjt.css';
import '../../css/m/m9cbxbbqp.css';
import '../../css/q/qi32o3t-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="astguezjt"/><path class="m9cbxbbqp"/><path class="qi32o3t-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:crossedflags" /></template>
