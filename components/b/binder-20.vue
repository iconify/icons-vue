<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx89adb5k.css';
import '../../css/k/ktkk4-3nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bx89adb5k"/><path class="ktkk4-3nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:binder-20" /></template>
