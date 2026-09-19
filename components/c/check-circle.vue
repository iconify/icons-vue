<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgq1o5bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgq1o5bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-circle" /></template>
