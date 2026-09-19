<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7msnsb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7msnsb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-asia-filled" /></template>
