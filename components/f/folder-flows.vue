<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av9wombmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="av9wombmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-flows" /></template>
