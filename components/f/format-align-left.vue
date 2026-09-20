<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhjllqb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bhjllqb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-align-left" /></template>
