<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trilp1bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trilp1bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-arrow-path" /></template>
