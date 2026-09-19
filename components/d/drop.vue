<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/ssi7s1biy.css';
import '../../css/m/md286fbip.css';
import '../../css/f/fcx7apbsu.css';
import '../../css/o/ouisgrmwz.css';
import '../../css/z/zyqtc0b3c.css';
import '../../css/v/vevvsobzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="ssi7s1biy"/><g class="md286fbip"><path class="fcx7apbsu"/><path class="ouisgrmwz"/><path class="zyqtc0b3c"/><path class="vevvsobzj"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:drop" /></template>
