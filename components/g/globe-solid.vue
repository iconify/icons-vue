<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oegqqvbgf.css';
import '../../css/d/di6z7bc9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oegqqvbgf"/><path class="di6z7bc9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:globe-solid" /></template>
