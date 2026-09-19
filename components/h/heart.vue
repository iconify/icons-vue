<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ify7xnn5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ify7xnn5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:heart" /></template>
