<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vprz48biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vprz48biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-merge" /></template>
