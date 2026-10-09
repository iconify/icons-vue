<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-g74icta.css';
import '../../css/c/ci72u-bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="ci72u-bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-20" /></template>
