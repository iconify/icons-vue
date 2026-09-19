<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu1vs1ngp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu1vs1ngp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-02" /></template>
