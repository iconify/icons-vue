<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_1j6lb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_1j6lb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:badge" /></template>
