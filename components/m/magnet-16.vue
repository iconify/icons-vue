<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyvy4ik0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kyvy4ik0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:magnet-16" /></template>
