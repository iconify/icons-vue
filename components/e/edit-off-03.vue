<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w02dggg3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w02dggg3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:edit-off-03" /></template>
