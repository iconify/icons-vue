<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzgij3q9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wzgij3q9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:fork-knife-20-solid" /></template>
