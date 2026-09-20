<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dahkt0btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dahkt0btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:live-photo-filled" /></template>
