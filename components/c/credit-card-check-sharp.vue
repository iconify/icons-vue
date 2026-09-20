<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wes4atb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wes4atb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-check-sharp" /></template>
