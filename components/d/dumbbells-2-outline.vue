<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymv_wy09c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ymv_wy09c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbells-2-outline" /></template>
