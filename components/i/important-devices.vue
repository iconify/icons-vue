<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leul54bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leul54bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:important-devices" /></template>
