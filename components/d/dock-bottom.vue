<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9i5tddcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9i5tddcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dock-bottom" /></template>
