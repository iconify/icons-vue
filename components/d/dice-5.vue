<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfcci4bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfcci4bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dice-5" /></template>
