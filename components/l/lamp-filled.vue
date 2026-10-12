<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9ha_eclp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9ha_eclp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lamp-filled" /></template>
