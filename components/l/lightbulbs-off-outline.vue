<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn5gwnb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn5gwnb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulbs-off-outline" /></template>
