<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgvde7qwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgvde7qwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alphabet-greek" /></template>
