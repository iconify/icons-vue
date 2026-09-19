<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph9q5h07s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ph9q5h07s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:capslock" /></template>
