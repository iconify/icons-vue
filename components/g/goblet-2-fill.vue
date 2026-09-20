<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df0rsdq2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df0rsdq2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goblet-2-fill" /></template>
