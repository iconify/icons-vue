<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw6eewayi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw6eewayi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:flask" /></template>
