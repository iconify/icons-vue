<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es5er9stz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es5er9stz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eject-circle-outline" /></template>
