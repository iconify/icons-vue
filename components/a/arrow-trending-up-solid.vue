<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-9fldx0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-9fldx0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-trending-up-solid" /></template>
