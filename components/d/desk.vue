<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms3homc2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms3homc2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:desk" /></template>
