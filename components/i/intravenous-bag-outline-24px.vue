<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2m81sbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2m81sbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:intravenous-bag-outline-24px" /></template>
