<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amqo51b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="amqo51b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-under-gabled-roof" /></template>
