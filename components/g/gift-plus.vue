<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt4un_bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt4un_bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gift-plus" /></template>
