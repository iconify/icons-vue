<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c978-abib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c978-abib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-2-fill" /></template>
