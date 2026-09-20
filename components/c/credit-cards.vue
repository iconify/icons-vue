<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekmfh7bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ekmfh7bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:credit-cards" /></template>
