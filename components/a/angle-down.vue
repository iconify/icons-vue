<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5t11gb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5t11gb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:angle-down" /></template>
