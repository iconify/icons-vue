<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_jw3abuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_jw3abuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gmail" /></template>
