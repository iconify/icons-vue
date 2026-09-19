<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiwcx9z6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uiwcx9z6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-ubuntu" /></template>
