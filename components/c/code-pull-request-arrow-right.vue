<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c84wutbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c84wutbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:code-pull-request-arrow-right" /></template>
