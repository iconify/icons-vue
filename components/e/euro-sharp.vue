<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zziz7bc6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zziz7bc6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:euro-sharp" /></template>
