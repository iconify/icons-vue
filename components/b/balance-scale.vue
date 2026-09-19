<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yvw2c1gyq.css';
import '../../css/v/vkv4itg_l.css';
import '../../css/w/wb4p8zbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="yvw2c1gyq"/><path class="vkv4itg_l"/><path class="wb4p8zbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:balance-scale" /></template>
