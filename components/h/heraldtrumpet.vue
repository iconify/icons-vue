<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9_kcp0_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="w9_kcp0_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:heraldtrumpet" /></template>
