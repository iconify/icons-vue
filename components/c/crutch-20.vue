<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2v6vtbhe.css';
import '../../css/j/jvjk3qbkk.css';
import '../../css/h/h96qerq4e.css';
import '../../css/s/sinjhb0df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j2v6vtbhe"/><path class="jvjk3qbkk"/><path class="h96qerq4e"/><path class="sinjhb0df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crutch-20" /></template>
