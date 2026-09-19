<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj-z-xb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uj-z-xb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-up-solid" /></template>
