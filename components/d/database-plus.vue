<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zml5j5fup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zml5j5fup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:database-plus" /></template>
