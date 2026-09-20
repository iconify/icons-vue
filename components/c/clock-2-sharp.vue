<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgnm92b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgnm92b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-2-sharp" /></template>
