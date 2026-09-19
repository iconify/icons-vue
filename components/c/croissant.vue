<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj33xlbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj33xlbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:croissant" /></template>
