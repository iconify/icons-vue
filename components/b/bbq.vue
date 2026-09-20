<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac_7zloqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ac_7zloqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bbq" /></template>
