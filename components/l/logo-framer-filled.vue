<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si7uhab_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si7uhab_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-framer-filled" /></template>
