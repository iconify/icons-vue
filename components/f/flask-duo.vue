<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsfq9iban.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g_-wzjb_l.css';
import '../../css/z/zxv-swbgq.css';
import '../../css/z/z8axxibzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsfq9iban secondary"/><g class="dt0cm9dhy primary"><path class="g_-wzjb_l"/><path class="zxv-swbgq"/><path class="z8axxibzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flask-duo" /></template>
