<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozv103bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozv103bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-heading-decease" /></template>
