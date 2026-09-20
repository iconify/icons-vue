<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5cslrb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5cslrb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-dots-2-filled" /></template>
