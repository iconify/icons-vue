<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9b89bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="li9b89bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-peace" /></template>
