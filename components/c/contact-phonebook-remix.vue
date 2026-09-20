<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfcqc8pth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qfcqc8pth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:contact-phonebook-remix" /></template>
