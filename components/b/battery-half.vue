<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbwazrb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbwazrb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:battery-half" /></template>
