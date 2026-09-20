<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr7rw0bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dr7rw0bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:database" /></template>
