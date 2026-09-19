<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgfuf6b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zgfuf6b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:book-solid" /></template>
