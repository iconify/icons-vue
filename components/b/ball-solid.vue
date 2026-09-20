<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms3yp7bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ms3yp7bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ball-solid" /></template>
