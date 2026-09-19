<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sypfpluiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="sypfpluiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hdd" /></template>
