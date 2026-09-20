<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3i8dxbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l3i8dxbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:contact-phonebook-solid" /></template>
