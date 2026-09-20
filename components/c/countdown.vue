<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l-ca2edhw.css';
import '../../css/w/w-lvmjg0i.css';
import '../../css/g/gsbedy41l.css';
import '../../css/a/a26ez0-6d.css';
import '../../css/r/rh90to7ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l-ca2edhw"/><path class="w-lvmjg0i"/><path clip-rule="evenodd" class="gsbedy41l"/><path clip-rule="evenodd" class="a26ez0-6d"/><path clip-rule="evenodd" class="rh90to7ou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:countdown" /></template>
