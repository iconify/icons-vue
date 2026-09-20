<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biid27bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biid27bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-signal" /></template>
