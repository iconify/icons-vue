<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7hbz4i7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7hbz4i7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-cloudflare" /></template>
