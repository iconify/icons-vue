<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxz9n17ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rxz9n17ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:crate" /></template>
