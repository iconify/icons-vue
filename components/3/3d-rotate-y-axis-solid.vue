<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh8q-t_re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kh8q-t_re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:3d-rotate-y-axis-solid" /></template>
