<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfi6zzj9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfi6zzj9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-watch-alt" /></template>
