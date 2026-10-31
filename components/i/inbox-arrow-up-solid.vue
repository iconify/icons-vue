<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tii4-acje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tii4-acje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:inbox-arrow-up-solid" /></template>
