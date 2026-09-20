<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klt7ieb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klt7ieb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-electric" /></template>
