<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk-yam33n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk-yam33n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-down" /></template>
