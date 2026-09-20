<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrabrcp1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrabrcp1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:local-offer" /></template>
