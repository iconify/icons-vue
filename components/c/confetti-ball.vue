<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhpwv3ssp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vhpwv3ssp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:confetti-ball" /></template>
