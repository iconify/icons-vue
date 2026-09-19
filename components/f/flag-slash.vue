<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3f_t1esf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c3f_t1esf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:flag-slash" /></template>
