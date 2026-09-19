<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkrglpb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkrglpb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-phone" /></template>
