<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho57073-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ho57073-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockerizalo-dark" /></template>
