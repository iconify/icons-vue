<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa7v1s--s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa7v1s--s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-expressionless-sharp" /></template>
