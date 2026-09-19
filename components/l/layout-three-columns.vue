<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb9dqsb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nb9dqsb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:layout-three-columns" /></template>
