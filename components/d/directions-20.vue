<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_g719pny.css';
import '../../css/a/abx7eg41v.css';
import '../../css/x/x9j18ffun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_g719pny"/><path class="abx7eg41v"/><path class="x9j18ffun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:directions-20" /></template>
