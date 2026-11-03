<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4ep1nn3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z4ep1nn3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:anchor-20-solid" /></template>
