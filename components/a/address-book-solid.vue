<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csrk5ubwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csrk5ubwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:address-book-solid" /></template>
