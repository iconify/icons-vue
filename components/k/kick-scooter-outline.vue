<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csyuqibvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csyuqibvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kick-scooter-outline" /></template>
