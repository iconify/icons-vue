<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqmehdb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqmehdb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-2-fill" /></template>
