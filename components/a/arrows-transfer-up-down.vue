<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t67i64bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t67i64bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-transfer-up-down" /></template>
