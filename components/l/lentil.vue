<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwdk8rb8z.css';
import '../../css/g/g32g6sb1v.css';
import '../../css/w/w5iegtdxh.css';
import '../../css/o/or1tl4bac.css';
import '../../css/j/j2po2xbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cwdk8rb8z"/><path class="g32g6sb1v"/><path class="w5iegtdxh"/><path class="or1tl4bac"/><path class="j2po2xbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:lentil" /></template>
