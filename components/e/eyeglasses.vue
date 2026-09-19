<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skqn11soa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="skqn11soa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:eyeglasses" /></template>
