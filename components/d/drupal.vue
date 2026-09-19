<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tesji1z-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="tesji1z-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:drupal" /></template>
