<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhknbhbfu.css';
import '../../css/c/c65-ehvfy.css';
import '../../css/o/owu6fcc5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lhknbhbfu"/><path class="c65-ehvfy"/><path class="owu6fcc5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:furnace-48" /></template>
