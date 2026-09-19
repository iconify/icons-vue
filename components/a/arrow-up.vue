<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe513_xmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe513_xmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-up" /></template>
