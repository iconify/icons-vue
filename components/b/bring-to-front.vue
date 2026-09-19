<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pea7082vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pea7082vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bring-to-front" /></template>
