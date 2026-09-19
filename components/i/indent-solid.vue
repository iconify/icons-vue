<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epj4bbkgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="epj4bbkgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:indent-solid" /></template>
