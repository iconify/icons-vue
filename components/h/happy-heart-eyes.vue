<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp7g7fret.css';
import '../../css/b/bwibdw4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp7g7fret"/><path class="bwibdw4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:happy-heart-eyes" /></template>
