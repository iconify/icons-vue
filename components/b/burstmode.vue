<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuw81ib3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="kuw81ib3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:burstmode" /></template>
