<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex9-ukb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex9-ukb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:input-ai" /></template>
