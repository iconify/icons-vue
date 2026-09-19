<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpik4gbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rpik4gbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-activitybar-right" /></template>
