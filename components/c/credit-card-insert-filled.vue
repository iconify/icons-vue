<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux-9n-b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux-9n-b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:credit-card-insert-filled" /></template>
