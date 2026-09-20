<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjqv5cbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjqv5cbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-florin" /></template>
