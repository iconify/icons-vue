<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuf9y1byy.css';
import '../../css/o/oo7eexbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuf9y1byy"/><path class="oo7eexbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forbidden-bold" /></template>
