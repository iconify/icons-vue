<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev10k0bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev10k0bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x3-solid" /></template>
