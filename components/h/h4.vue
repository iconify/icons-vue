<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/virf4bbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="virf4bbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h4" /></template>
