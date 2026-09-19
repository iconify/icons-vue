<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riagsac2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riagsac2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dialpad-circle-02" /></template>
