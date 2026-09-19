<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p81y391ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="p81y391ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:fog" /></template>
