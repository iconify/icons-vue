<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejfnnz0pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejfnnz0pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:key-filled" /></template>
