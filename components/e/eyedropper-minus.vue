<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b08b-lb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b08b-lb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eyedropper-minus" /></template>
