<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8l3hzstz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j8l3hzstz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:briefcase-alt" /></template>
