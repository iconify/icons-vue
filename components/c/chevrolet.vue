<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6mmyob4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6mmyob4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chevrolet" /></template>
