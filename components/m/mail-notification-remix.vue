<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgp00ubed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hgp00ubed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-notification-remix" /></template>
