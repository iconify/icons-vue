<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku189v24n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku189v24n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brain-fill" /></template>
