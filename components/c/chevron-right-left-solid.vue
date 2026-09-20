<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svl07cy6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svl07cy6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-right-left-solid" /></template>
