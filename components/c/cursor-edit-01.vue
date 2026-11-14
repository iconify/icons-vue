<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dum2c-ydw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dum2c-ydw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-edit-01" /></template>
