<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf11exb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sf11exb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:ellipsis-v" /></template>
