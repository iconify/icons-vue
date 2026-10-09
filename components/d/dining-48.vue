<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsaiwdb4t.css';
import '../../css/b/bwry4rblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsaiwdb4t"/><path class="bwry4rblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dining-48" /></template>
