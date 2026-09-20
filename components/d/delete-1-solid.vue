<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaaaky2zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oaaaky2zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:delete-1-solid" /></template>
