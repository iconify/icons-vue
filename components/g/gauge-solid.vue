<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks9q9jbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks9q9jbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gauge-solid" /></template>
