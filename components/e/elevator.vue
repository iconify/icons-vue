<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljctvqvlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":833,"height":1024};
const content = `<path class="ljctvqvlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:elevator" /></template>
