<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-xxz-ihp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-xxz-ihp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clipboard-check-solid" /></template>
