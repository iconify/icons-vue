<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz35pabwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz35pabwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-office-2-solid" /></template>
