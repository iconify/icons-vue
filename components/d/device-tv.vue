<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovno7d_nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovno7d_nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-tv" /></template>
