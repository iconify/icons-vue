<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9xf8n8nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9xf8n8nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gem-alt" /></template>
