<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svqoymb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svqoymb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-x-filled" /></template>
