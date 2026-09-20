<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptk_lvjba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptk_lvjba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-t" /></template>
