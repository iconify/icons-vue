<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5lckz1mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m5lckz1mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x2-20-solid" /></template>
