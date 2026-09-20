<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahj3yaccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahj3yaccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-nextjs" /></template>
