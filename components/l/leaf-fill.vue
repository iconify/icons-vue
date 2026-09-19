<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br4hz9-6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="br4hz9-6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:leaf-fill" /></template>
