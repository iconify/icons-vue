<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb-3bsb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb-3bsb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:captioning-solid" /></template>
