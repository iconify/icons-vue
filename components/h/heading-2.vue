<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgp3vi4ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgp3vi4ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-2" /></template>
