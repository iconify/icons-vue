<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn0-sbcys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="pn0-sbcys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:electronjs" /></template>
