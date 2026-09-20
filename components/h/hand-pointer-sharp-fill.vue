<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ex82bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_ex82bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-sharp-fill" /></template>
