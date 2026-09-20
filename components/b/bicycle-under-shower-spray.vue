<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5i5ttbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g5i5ttbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-under-shower-spray" /></template>
