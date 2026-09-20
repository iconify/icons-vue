<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-n6ud5vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-n6ud5vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-fast" /></template>
