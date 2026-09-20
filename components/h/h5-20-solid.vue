<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb6_mlbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pb6_mlbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h5-20-solid" /></template>
