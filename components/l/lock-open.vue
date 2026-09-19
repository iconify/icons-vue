<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1q9abne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jg1q9abne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:lock-open" /></template>
