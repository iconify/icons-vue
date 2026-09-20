<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la2-7fq6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la2-7fq6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-sharp-fill" /></template>
