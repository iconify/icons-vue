<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khfv6mq6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="khfv6mq6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:inbox-content-remix" /></template>
