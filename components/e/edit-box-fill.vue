<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbx2phzgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbx2phzgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:edit-box-fill" /></template>
