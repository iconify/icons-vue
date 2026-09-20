<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go8ehsr3x.css';
import '../../css/z/zut4dr69s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="go8ehsr3x"/><path class="zut4dr69s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:copyright" /></template>
