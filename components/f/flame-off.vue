<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw-430x6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw-430x6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flame-off" /></template>
