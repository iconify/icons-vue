<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eibxe6d8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eibxe6d8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:first-page" /></template>
