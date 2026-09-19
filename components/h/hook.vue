<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyleo_4xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wyleo_4xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:hook" /></template>
