<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp-n3fbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp-n3fbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:aimass" /></template>
