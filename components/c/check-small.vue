<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmrs85b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmrs85b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:check-small" /></template>
