<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbmr7ioil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbmr7ioil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-3x2" /></template>
