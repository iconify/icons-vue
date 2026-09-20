<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu2vlpzoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu2vlpzoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-w-filled" /></template>
