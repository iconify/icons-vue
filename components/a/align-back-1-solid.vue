<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnids9u8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mnids9u8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:align-back-1-solid" /></template>
