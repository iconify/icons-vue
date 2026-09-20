<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aygsrugvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygsrugvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:garden-cart-filled" /></template>
