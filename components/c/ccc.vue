<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3uq27-sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3uq27-sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ccc" /></template>
