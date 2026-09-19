<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h16k0hb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h16k0hb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lock-closed-20-solid" /></template>
