<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhj7tk-5q.css';
import '../../css/k/ktfgl0b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj7tk-5q"/><path clip-rule="evenodd" class="ktfgl0b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-cloud-bold" /></template>
