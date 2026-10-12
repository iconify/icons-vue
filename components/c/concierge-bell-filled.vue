<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eioub-k-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eioub-k-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:concierge-bell-filled" /></template>
