<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpggglb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jpggglb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-plus-16-solid" /></template>
