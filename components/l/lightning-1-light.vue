<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buv1006ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buv1006ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lightning-1-light" /></template>
