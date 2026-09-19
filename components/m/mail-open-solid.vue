<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo9gfy0rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oo9gfy0rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:mail-open-solid" /></template>
