<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c93967rjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c93967rjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading-04" /></template>
