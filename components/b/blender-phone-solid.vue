<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf6tr1s3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf6tr1s3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:blender-phone-solid" /></template>
