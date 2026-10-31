<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwxonpa1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gwxonpa1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:check-double-20-solid" /></template>
