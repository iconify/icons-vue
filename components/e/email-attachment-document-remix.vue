<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie1jvqbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ie1jvqbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:email-attachment-document-remix" /></template>
