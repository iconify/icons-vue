<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir3tr1blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir3tr1blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:icon" /></template>
