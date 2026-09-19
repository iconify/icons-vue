<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9abhdcbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p9abhdcbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-europe-africa-20-solid" /></template>
