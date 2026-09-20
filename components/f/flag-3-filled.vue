<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak6i94bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak6i94bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flag-3-filled" /></template>
