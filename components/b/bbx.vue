<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9jlgbc2j.css';
import '../../css/f/fnvhz6b_d.css';
import '../../css/r/r20ki5l4i.css';
import '../../css/w/w4w5jo-zd.css';
import '../../css/u/uys7csb9y.css';
import '../../css/y/yqd87jbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z9jlgbc2j"/><path class="fnvhz6b_d"/><path class="r20ki5l4i"/><path class="w4w5jo-zd"/><path class="uys7csb9y"/><path class="yqd87jbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:bbx" /></template>
