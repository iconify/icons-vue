<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-c2luh3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-c2luh3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:layout-right-sidebar" /></template>
