<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnfbg9tya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnfbg9tya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-cog-outline" /></template>
