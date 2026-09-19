<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kirngkbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kirngkbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lifebuoy-20-solid" /></template>
