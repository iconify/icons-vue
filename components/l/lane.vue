<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2hi92bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2hi92bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lane" /></template>
