<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azef4rb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="azef4rb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-under-list-beside-checkmark" /></template>
