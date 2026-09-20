<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ac9yb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ac9yb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:accessible-filled" /></template>
