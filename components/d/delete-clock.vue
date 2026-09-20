<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqd6b-bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqd6b-bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:delete-clock" /></template>
