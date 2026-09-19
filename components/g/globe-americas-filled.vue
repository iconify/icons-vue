<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0m4k5a2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0m4k5a2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-americas-filled" /></template>
