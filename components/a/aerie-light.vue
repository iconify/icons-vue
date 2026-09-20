<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w14l44ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w14l44ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aerie-light" /></template>
