<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi0xuvbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi0xuvbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-down-right" /></template>
