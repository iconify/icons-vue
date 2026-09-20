<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjof12r2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjof12r2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-sharp-fill" /></template>
