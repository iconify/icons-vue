<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5hklmbye.css';
import '../../css/d/d-1rjbc-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5hklmbye"/><path class="d-1rjbc-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folders-filled" /></template>
