<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9n_ivbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9n_ivbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-h-filled" /></template>
