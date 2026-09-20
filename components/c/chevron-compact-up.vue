<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxs94ebsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxs94ebsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chevron-compact-up" /></template>
