<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm2pvabdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm2pvabdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coil" /></template>
