<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejek3_b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ejek3_b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-under-list-beside-checkmark" /></template>
