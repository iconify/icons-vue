<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9ay-2b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ay-2b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-minimise" /></template>
