<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw6pfwb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kw6pfwb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diploma-verified-outline" /></template>
