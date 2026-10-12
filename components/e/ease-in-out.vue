<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbvjjbsbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbvjjbsbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:ease-in-out" /></template>
