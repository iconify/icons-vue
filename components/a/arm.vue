<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6c71_qzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6c71_qzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:arm" /></template>
