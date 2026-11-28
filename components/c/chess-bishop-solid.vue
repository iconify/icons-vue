<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc8awf2mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc8awf2mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-bishop-solid" /></template>
