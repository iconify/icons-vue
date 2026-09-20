<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miys4ebmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miys4ebmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gamepad-solid" /></template>
