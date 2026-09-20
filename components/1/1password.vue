<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhzopbb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhzopbb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:1password" /></template>
