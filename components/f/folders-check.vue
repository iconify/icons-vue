<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwihqz_pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwihqz_pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folders-check" /></template>
