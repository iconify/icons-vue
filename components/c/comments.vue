<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6zz21_5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v6zz21_5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:comments" /></template>
