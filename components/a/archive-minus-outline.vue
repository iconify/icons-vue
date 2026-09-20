<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyiwk_buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyiwk_buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-minus-outline" /></template>
