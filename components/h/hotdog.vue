<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-vm5ubxp.css';
import '../../css/w/w54lu2b9d.css';
import '../../css/h/h432u9bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-vm5ubxp"/><path class="w54lu2b9d"/><path class="h432u9bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:hotdog" /></template>
