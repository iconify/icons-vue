<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm9z_7bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pm9z_7bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:car-20-solid" /></template>
