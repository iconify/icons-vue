<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m062yj1wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m062yj1wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:hsbc" /></template>
