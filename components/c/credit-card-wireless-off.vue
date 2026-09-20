<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ih2k-9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4ih2k-9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-wireless-off" /></template>
