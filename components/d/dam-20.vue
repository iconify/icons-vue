<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0-dfyl4d.css';
import '../../css/b/bbqv1obqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f0-dfyl4d"/><path class="bbqv1obqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dam-20" /></template>
