<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apq2pw-va.css';
import '../../css/f/fjn5fnnqh.css';
import '../../css/x/xs7xk1ywk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="apq2pw-va"/><path class="fjn5fnnqh"/><path class="xs7xk1ywk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fan-20" /></template>
