<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehfjs3bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ehfjs3bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-under-key" /></template>
