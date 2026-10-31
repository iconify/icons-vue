<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_i4rwxkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w_i4rwxkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cookie-20-solid" /></template>
