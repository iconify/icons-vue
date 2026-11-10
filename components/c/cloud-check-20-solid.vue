<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9zz1bb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j9zz1bb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-check-20-solid" /></template>
