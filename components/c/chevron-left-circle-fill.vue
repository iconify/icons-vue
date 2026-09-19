<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku7oqxm4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ku7oqxm4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-left-circle-fill" /></template>
