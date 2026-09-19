<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-sd3vb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":44,"height":24};
const content = `<path clip-rule="evenodd" class="y-sd3vb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:button" /></template>
