<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r37d31ykc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r37d31ykc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:at" /></template>
