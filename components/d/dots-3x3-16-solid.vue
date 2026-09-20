<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s94owgr7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s94owgr7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x3-16-solid" /></template>
