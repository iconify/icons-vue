<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvd1dhbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvd1dhbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-aws" /></template>
