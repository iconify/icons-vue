<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq4o54ofz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kq4o54ofz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:coffee-mug-remix" /></template>
