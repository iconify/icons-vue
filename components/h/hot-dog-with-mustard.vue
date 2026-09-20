<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u02ts_bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u02ts_bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hot-dog-with-mustard" /></template>
