<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om31gr9fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="om31gr9fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-up-circle-fill" /></template>
