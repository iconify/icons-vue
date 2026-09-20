<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12i2fc3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i12i2fc3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cryengine" /></template>
