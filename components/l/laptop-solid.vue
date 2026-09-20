<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grzo6xb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="grzo6xb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:laptop-solid" /></template>
