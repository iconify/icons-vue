<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtjzwnbwv.css';
import '../../css/d/dbws_7b9j.css';
import '../../css/l/lyi1fbbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjzwnbwv"/><path class="dbws_7b9j"/><path class="lyi1fbbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-outline" /></template>
