<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r42rcsbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r42rcsbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-number-3-filled" /></template>
