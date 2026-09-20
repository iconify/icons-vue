<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei_iqhb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ei_iqhb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dropbox-logo-remix" /></template>
