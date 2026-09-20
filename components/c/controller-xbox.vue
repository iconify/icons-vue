<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn56070pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn56070pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-xbox" /></template>
