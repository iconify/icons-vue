<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfmqexbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gfmqexbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-right-20-solid" /></template>
