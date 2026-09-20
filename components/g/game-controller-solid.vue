<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_fd73x_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t_fd73x_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:game-controller-solid" /></template>
