<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxj4adbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xxj4adbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:house" /></template>
