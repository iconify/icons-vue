<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxd1ljp-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxd1ljp-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-digital" /></template>
