<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7rr8ab4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x7rr8ab4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:gallery-2-solid" /></template>
