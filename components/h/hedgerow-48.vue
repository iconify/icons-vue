<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg--s-b0r.css';
import '../../css/o/ozim3qb0g.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mg--s-b0r"/><path class="ozim3qb0g"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hedgerow-48" /></template>
