<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur4kl4b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur4kl4b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-douban" /></template>
