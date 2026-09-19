<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s59fp7b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s59fp7b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:edit-page" /></template>
