<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weuip4crh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="weuip4crh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gender-female-16-solid" /></template>
