<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti2etsb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti2etsb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-yahoo" /></template>
