<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efz48nbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="efz48nbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graphic-template-website-ui-solid" /></template>
