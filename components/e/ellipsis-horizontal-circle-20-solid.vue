<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw5tsgxnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="aw5tsgxnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-horizontal-circle-20-solid" /></template>
