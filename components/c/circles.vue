<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwvql_bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvql_bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circles" /></template>
