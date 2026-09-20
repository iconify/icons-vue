<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo78k0b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo78k0b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-azure" /></template>
