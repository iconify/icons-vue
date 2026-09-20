<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guc4irqmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guc4irqmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-square-rounded-filled" /></template>
