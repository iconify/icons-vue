<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whof3db5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whof3db5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-filled" /></template>
