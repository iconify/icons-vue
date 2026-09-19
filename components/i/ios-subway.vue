<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at9237b-b.css';
import '../../css/t/t0f-scclc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="at9237b-b"/><path class="t0f-scclc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-subway" /></template>
