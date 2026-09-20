<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz1dp7iva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz1dp7iva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:audio-lines-sharp" /></template>
