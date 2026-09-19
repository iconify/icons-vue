<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-0j3bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-0j3bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:checked-box-solid" /></template>
