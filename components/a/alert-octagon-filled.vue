<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgx4pib1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgx4pib1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alert-octagon-filled" /></template>
