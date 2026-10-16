<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-3_n6vyt.css';
import '../../css/x/x2br98bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-3_n6vyt"/><path class="x2br98bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chisel-48" /></template>
