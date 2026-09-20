<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-2i7nb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-2i7nb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-bottom-sharp-fill" /></template>
