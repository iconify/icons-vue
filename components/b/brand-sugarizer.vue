<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1fep24eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1fep24eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-sugarizer" /></template>
