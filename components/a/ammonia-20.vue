<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gliza6bbj.css';
import '../../css/x/x8oc9s62k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gliza6bbj"/><path class="x8oc9s62k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ammonia-20" /></template>
