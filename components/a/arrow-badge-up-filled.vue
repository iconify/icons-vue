<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1fz2zb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1fz2zb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-badge-up-filled" /></template>
