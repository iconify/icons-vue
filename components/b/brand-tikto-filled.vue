<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk8flv62h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8flv62h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-tikto-filled" /></template>
