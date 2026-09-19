<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn1j3bxoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn1j3bxoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:antenna" /></template>
