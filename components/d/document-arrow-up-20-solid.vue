<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m18kcqbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m18kcqbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-arrow-up-20-solid" /></template>
