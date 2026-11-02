<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phhdg-b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phhdg-b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-digit-fill" /></template>
