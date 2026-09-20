<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhac42-nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhac42-nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-deviantart" /></template>
