<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihqw2pbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ihqw2pbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-euro-20-solid" /></template>
