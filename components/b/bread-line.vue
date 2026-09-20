<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmtm7pz0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmtm7pz0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bread-line" /></template>
