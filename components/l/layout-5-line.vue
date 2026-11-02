<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-4hrvbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-4hrvbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-5-line" /></template>
