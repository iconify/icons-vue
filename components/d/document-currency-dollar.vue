<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omzu0k0ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omzu0k0ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-dollar" /></template>
