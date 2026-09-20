<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqbub0eaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqbub0eaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:application-add" /></template>
