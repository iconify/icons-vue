<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4vl4e8qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4vl4e8qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:glasses-filled" /></template>
