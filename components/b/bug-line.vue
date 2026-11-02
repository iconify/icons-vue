<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvjq57n0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvjq57n0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bug-line" /></template>
