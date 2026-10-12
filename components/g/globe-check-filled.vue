<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js-ju8bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js-ju8bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-check-filled" /></template>
