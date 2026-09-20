<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovd9g659q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovd9g659q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-top" /></template>
