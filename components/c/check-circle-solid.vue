<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyd11u1lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyd11u1lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check-circle-solid" /></template>
