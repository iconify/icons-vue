<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs13v40bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs13v40bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-wireless-off-outline" /></template>
