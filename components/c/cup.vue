<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az64tvbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az64tvbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cup" /></template>
