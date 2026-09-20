<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0xa18b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="h0xa18b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:delete" /></template>
