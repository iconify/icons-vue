<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioq81ya0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ioq81ya0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lifebuoy-solid" /></template>
