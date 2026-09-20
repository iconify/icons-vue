<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db0ssxsmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db0ssxsmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forbid-circle-line" /></template>
