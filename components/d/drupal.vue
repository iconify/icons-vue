<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cllix0kul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":488};
const content = `<path class="cllix0kul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:drupal" /></template>
