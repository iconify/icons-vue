<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef3cp9bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="ef3cp9bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:drupal" /></template>
