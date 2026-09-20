<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t38qr0est.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t38qr0est"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:check-round-fill" /></template>
