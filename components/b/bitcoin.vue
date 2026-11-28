<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrsc13pcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrsc13pcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bitcoin" /></template>
