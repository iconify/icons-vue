<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikywg0ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ikywg0ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:anchor" /></template>
