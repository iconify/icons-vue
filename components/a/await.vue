<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l95vq7mka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l95vq7mka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:await" /></template>
