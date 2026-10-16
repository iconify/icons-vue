<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kimfu9q5t.css';
import '../../css/d/df3qvvanp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kimfu9q5t"/><path class="df3qvvanp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-warning-20" /></template>
