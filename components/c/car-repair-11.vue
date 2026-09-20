<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6yzxzb0o.css';
import '../../css/k/kdqskdg1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="d6yzxzb0o"/><path class="kdqskdg1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car-repair-11" /></template>
