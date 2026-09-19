<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz7cuwb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vz7cuwb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layout-header-cells" /></template>
