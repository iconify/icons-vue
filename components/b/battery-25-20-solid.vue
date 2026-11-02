<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhriw0pwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bhriw0pwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-25-20-solid" /></template>
