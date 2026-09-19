<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzn7rdbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":448};
const content = `<path class="tzn7rdbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:checked" /></template>
