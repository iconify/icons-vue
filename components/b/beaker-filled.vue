<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi_7mx36a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b pi_7mx36a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:beaker-filled" /></template>
