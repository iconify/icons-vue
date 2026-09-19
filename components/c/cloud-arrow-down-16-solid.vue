<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-ddl3baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a-ddl3baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-arrow-down-16-solid" /></template>
