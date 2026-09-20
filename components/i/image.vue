<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9t5p3b5c.css';
import '../../css/o/ohfe1ob8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p9t5p3b5c"/><path class="ohfe1ob8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:image" /></template>
