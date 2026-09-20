<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzx4-eb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="zzx4-eb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:clipboard" /></template>
