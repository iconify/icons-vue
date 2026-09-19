<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6b8fdb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="b6b8fdb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:accounts" /></template>
